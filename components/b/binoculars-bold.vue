<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muwknjt7p.css';
import '../../css/b/b5jplqbkn.css';
import '../../css/b/bnrsc3bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muwknjt7p"/><path class="b5jplqbkn"/><path clip-rule="evenodd" class="bnrsc3bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:binoculars-bold" /></template>
