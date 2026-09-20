<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzomtlbvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzomtlbvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:flatpak" /></template>
