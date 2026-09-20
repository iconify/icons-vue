<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlpvp0iiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlpvp0iiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:castle-1-filled" /></template>
