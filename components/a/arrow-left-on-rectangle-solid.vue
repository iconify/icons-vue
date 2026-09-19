<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_o0smb-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n_o0smb-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-left-on-rectangle-solid" /></template>
