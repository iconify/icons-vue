<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecpj_td6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ecpj_td6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:bitbucket-logo-solid" /></template>
