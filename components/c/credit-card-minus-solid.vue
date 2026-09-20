<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypqjqacjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypqjqacjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:credit-card-minus-solid" /></template>
