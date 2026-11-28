<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8-t6_pqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8-t6_pqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:curtains-open-solid" /></template>
