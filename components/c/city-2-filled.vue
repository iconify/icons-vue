<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvy8sjoer.css';
import '../../css/b/b-nsf-bwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvy8sjoer"/><path class="b-nsf-bwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:city-2-filled" /></template>
