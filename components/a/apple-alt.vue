<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k55sakbtr.css';
import '../../css/i/ibrld782c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k55sakbtr"/><path class="ibrld782c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:apple-alt" /></template>
