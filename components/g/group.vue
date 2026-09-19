<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z3y9k2i2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z3y9k2i2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:group" /></template>
