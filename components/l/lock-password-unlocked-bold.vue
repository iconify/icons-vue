<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvu1ofbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hvu1ofbri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-password-unlocked-bold" /></template>
