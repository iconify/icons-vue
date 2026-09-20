<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hizcmjbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hizcmjbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:car-fan-auto" /></template>
