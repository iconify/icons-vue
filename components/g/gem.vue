<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmr9iccga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmr9iccga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:gem" /></template>
