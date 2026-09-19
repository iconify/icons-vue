<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tk315vbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tk315vbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:cloud-fog-filled" /></template>
