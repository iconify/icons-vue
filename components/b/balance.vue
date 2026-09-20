<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chowghc9o.css';
import '../../css/i/iuef7db3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chowghc9o"/><path class="iuef7db3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:balance" /></template>
