<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgf_6p6xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgf_6p6xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-top-simple-fill" /></template>
