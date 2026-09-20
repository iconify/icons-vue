<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uibqwacqf.css';
import '../../css/s/sz5bu0b9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uibqwacqf"/><path class="sz5bu0b9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:burger-arrow-right-duotone" /></template>
