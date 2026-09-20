<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl9d6f0ug.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nl9d6f0ug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-align-offset-bottom-fill" /></template>
