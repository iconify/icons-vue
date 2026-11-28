<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvm2gtbqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvm2gtbqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:empty-set-solid" /></template>
