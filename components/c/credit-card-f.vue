<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okta756uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="okta756uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:credit-card-f" /></template>
