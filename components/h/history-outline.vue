<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsv9zc4jv.css';
import '../../css/n/n74bk89qt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsv9zc4jv"/><path class="n74bk89qt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:history-outline" /></template>
