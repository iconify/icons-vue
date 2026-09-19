<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpc_zebhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mpc_zebhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:confirmations-0-filled" /></template>
