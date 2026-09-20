<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pns5a3bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="pns5a3bor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cost-estimate-solid" /></template>
