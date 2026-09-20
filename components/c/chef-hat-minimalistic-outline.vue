<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kxc-7ebru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxc-7ebru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chef-hat-minimalistic-outline" /></template>
