<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlvvtbc1o.css';
import '../../css/n/nvm0pnlsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlvvtbc1o"/><path class="nvm0pnlsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article" /></template>
