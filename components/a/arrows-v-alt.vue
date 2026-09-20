<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0-k9nbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0-k9nbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrows-v-alt" /></template>
