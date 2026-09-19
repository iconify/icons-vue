<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exa-61b8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="exa-61b8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-yandex-cloud" /></template>
