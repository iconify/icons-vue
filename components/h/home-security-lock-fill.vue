<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szv9ucwib.css';
import '../../css/x/xenb14b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szv9ucwib"/><path class="xenb14b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:home-security-lock-fill" /></template>
