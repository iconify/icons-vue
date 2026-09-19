<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyqfzub1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oyqfzub1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:link-broken-alt-02" /></template>
