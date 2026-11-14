<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uaej_g74q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uaej_g74q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:login-02" /></template>
