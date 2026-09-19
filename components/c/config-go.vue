<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m64hpwtxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="m64hpwtxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:config-go" /></template>
