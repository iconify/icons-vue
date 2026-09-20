<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zaywovj7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zaywovj7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:hand-holding-dollar-solid" /></template>
