<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_53bcn2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_53bcn2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:facebook-solid" /></template>
