<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xco31rbaj.css';
import '../../css/f/f_0-3nbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xco31rbaj"/><path class="f_0-3nbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:house-filled" /></template>
