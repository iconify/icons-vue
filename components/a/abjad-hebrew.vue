<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ns3rjtbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns3rjtbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:abjad-hebrew" /></template>
