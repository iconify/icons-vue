<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uawrme4my.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24.9,"height":34.2};
const content = `<path class="uawrme4my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fivetran" /></template>
