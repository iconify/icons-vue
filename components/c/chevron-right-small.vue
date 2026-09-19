<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnqof6pva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fnqof6pva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:chevron-right-small" /></template>
