<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybjym5b1h.css';
import '../../css/b/bjzsqyhqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ybjym5b1h"/><path class="bjzsqyhqp duoicon-primary-layer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:bell-badge" /></template>
