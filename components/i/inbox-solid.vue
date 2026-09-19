<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eajcmacpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eajcmacpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:inbox-solid" /></template>
