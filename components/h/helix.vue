<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jf09xehhc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf09xehhc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:helix" /></template>
