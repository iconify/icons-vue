<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr0-kzblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0-kzblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:koc" /></template>
