<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gm1jblb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gm1jblb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mail-dot-sharp" /></template>
