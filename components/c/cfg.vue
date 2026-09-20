<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v57h_hb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cfg" /></template>
<style>
.v57h_hb6y {
  d: path("M3.973 17.775A10.135 10.135 0 0 1 21 7.049l-.892.741a8.977 8.977 0 0 0-15.087 9.498zm14.803-8.867a7.24 7.24 0 1 0-5.896 11.786v-1.159a6.08 6.08 0 1 1 5.004-9.886zm-2.224 1.853a4.337 4.337 0 0 0-7.749 2.7a4.344 4.344 0 0 0 7.471 3.01l-.73-.909a3.18 3.18 0 0 1-5.582-2.102a3.186 3.186 0 0 1 5.704-1.952l.886-.74z");
}

</style>
