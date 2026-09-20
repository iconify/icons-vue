<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzx73-76o.css';
import '../../css/f/f6hx_4p6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzx73-76o"/><path class="f6hx_4p6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:avinoc" /></template>
