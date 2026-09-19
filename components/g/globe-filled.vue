<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eta2ckg2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eta2ckg2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:globe-filled" /></template>
