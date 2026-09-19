<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxv08ik5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxv08ik5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:genderless" /></template>
