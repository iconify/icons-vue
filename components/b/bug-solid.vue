<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfm03acay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sfm03acay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:bug-solid" /></template>
