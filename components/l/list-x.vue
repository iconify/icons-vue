<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bt73-jbgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bt73-jbgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:list-x" /></template>
