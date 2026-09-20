<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hm5t9tb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5t9tb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:library-books-line" /></template>
