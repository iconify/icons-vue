<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b6zt-3bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6zt-3bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:funnel-plus" /></template>
