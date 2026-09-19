<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aweiaacdd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aweiaacdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:globe-europe-africa" /></template>
