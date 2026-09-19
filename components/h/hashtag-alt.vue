<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovn3_lrud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovn3_lrud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:hashtag-alt" /></template>
