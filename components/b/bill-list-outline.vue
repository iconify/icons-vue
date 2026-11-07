<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yhw7bfbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yhw7bfbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bill-list-outline" /></template>
