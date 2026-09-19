<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us9dlyptw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us9dlyptw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:beaker-empty-filled" /></template>
