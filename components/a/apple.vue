<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf9kq2bup.css';
import '../../css/w/wmtrl-rww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf9kq2bup"/><path class="wmtrl-rww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:apple" /></template>
