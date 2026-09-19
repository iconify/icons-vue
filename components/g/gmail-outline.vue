<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxwf4h5in.css';
import '../../css/b/bqf--ueux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxwf4h5in"/><path clip-rule="evenodd" class="bqf--ueux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:gmail-outline" /></template>
