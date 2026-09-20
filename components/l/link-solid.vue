<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djf01d-5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="djf01d-5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:link-solid" /></template>
