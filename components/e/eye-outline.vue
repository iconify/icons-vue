<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2zxfobyr.css';
import '../../css/q/q6ywlpbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2zxfobyr"/><path class="q6ywlpbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:eye-outline" /></template>
