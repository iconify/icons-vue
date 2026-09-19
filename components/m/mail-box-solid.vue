<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cww7qob_b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cww7qob_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:mail-box-solid" /></template>
