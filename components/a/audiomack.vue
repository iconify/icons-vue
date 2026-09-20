<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iby20cb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iby20cb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:audiomack" /></template>
