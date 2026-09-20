<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezdg7vhee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ezdg7vhee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:layers-1-remix" /></template>
