<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rtaspevdd.css';
import '../../css/v/v206u3j4t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer rtaspevdd"/><path class="duoicon-primary-layer v206u3j4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:confetti" /></template>
