<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk43tvbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk43tvbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-plus-filled" /></template>
