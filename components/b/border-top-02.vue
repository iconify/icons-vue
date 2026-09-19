<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nym3mc6ux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nym3mc6ux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:border-top-02" /></template>
