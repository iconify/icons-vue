<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwoe27ber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wwoe27ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:earbuds-case2" /></template>
