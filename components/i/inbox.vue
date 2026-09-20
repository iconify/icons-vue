<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p0hon6-9l.css';
import '../../css/h/ht7052bix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0hon6-9l"/><path class="ht7052bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:inbox" /></template>
