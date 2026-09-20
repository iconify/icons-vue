<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io7iwj50t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="io7iwj50t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-closed-sharp" /></template>
