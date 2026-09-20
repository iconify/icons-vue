<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2rq36bvg.css';
import '../../css/s/s1qeddblx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s2rq36bvg"/><path class="s1qeddblx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:boolean-on-24" /></template>
