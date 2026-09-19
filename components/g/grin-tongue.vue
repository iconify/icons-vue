<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnfu69bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="cnfu69bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:grin-tongue" /></template>
