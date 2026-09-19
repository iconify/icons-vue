<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p21askxdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p21askxdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:call-02" /></template>
