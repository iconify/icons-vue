<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/afrs0sbhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="afrs0sbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:facebook-f" /></template>
