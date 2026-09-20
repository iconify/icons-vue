<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti696rbkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti696rbkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:direction-up-right" /></template>
