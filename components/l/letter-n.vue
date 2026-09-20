<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skjvdnbvw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skjvdnbvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-n" /></template>
