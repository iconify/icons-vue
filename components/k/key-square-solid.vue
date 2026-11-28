<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cnxnubcxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cnxnubcxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:key-square-solid" /></template>
