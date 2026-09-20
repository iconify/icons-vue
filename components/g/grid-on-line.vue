<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_594-9bz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_594-9bz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:grid-on-line" /></template>
