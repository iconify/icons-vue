<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ernn07bjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ernn07bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:chakra-ui" /></template>
