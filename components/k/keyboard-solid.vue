<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_n9pmb7s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="f_n9pmb7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:keyboard-solid" /></template>
