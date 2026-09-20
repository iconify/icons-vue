<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlr1md4hf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vlr1md4hf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:list-ui-alt" /></template>
