<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7h45sbre.css';
import '../../css/s/s1zok783v.css';
import '../../css/a/a53wavbxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7h45sbre"/><path class="s1zok783v"/><path class="a53wavbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:eye-opened-duotone" /></template>
