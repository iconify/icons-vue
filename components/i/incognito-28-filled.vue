<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="oe319cpfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:incognito-28-filled" /></template>
<style>
.oe319cpfs {
  fill: currentColor;
  d: path("M20.5 14a5.5 5.5 0 1 1-5.447 6.25h-2.106A5.5 5.5 0 1 1 7.5 14a5.5 5.5 0 0 1 5.447 4.75h2.106A5.5 5.5 0 0 1 20.5 14m-13 1.5a4 4 0 1 0 0 8a4 4 0 0 0 0-8m13 0a4 4 0 1 0 0 8a4 4 0 0 0 0-8M17.174 3a3.75 3.75 0 0 1 3.36 2.084l2.888 5.824c.611.144 1.084.282 1.429.395c.241.079.475.17.71.264l.002.001l.002.001a.75.75 0 0 1-.629 1.362h.002a6 6 0 0 0-.554-.202a18 18 0 0 0-1.911-.495c-1.759-.364-4.52-.734-8.473-.734s-6.714.37-8.473.734c-.879.182-1.508.363-1.91.495a6 6 0 0 0-.554.203h-.001a.75.75 0 0 1-.626-1.363l.002-.002l.193-.08c.118-.046.29-.11.518-.184a18 18 0 0 1 1.43-.396l2.89-5.823A3.75 3.75 0 0 1 10.829 3z");
}

</style>
