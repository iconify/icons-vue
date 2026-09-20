<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvm2q8ssv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvm2q8ssv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:akaunting" /></template>
