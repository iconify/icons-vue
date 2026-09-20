<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gqi2oibfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gqi2oibfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-align-offset-left-sharp-fill" /></template>
