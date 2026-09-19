<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/avar3dbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="avar3dbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:disability-02" /></template>
