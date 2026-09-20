<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgb0fnbow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgb0fnbow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:link-h" /></template>
