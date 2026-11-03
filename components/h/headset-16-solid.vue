<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yylkgnb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yylkgnb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:headset-16-solid" /></template>
