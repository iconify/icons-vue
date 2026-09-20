<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmzjdnbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmzjdnbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-national-geographic" /></template>
