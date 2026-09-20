<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzx8o9bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzx8o9bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:connect-without-contact" /></template>
