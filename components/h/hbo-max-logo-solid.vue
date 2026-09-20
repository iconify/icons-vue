<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bozhqyb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bozhqyb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:hbo-max-logo-solid" /></template>
