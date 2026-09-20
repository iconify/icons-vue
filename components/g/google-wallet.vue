<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5kg9zf_c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5kg9zf_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:google-wallet" /></template>
