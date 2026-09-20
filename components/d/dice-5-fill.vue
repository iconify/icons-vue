<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngqnlhnvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ngqnlhnvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:dice-5-fill" /></template>
