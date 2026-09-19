<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqxw4t2sy.css';
import '../../css/i/iq2exjbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer hqxw4t2sy"/><path class="duoicon-primary-layer iq2exjbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:briefcase" /></template>
