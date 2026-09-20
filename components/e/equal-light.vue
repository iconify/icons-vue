<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixkz_u45r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixkz_u45r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:equal-light" /></template>
