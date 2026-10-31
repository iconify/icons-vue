<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_paa_jws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q_paa_jws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:face-smile-plus-solid" /></template>
