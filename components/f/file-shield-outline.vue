<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l98ww57lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l98ww57lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:file-shield-outline" /></template>
