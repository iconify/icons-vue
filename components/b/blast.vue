<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rhscw0hrm.css';
import '../../css/k/k0dg-7b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhscw0hrm"/><path class="k0dg-7b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:blast" /></template>
