<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au2sf5mhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="au2sf5mhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:gender-femme" /></template>
