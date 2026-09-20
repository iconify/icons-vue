<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4-97lbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d4-97lbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:columns-fill" /></template>
