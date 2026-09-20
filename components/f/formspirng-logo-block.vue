<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mza5crb4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mza5crb4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:formspirng-logo-block" /></template>
