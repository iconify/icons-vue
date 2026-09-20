<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v4or_ln8c.css';
import '../../css/p/pmdjauv5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4or_ln8c"/><path class="pmdjauv5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-ban-light" /></template>
