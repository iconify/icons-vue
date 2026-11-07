<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/er09-obpj.css';
import '../../css/w/w_8qokj7u.css';
import '../../css/k/ku79fqbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="er09-obpj"/><path class="w_8qokj7u"/><path clip-rule="evenodd" class="ku79fqbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:dropper-3-outline" /></template>
