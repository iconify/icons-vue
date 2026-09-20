<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq8lsbcnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq8lsbcnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:google-drive-solid" /></template>
