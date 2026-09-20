<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bosqagb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:curtains-sharp" /></template>
<style>
.bosqagb8f {
  fill: currentColor;
  d: path("M3 20v-1h2V4h14v15h2v1zm4.11-8q1.988.856 3.067 2.883T11.45 19h1.1q.194-2.09 1.273-4.117T16.891 12q-2.008-.856-3.087-2.883T12.53 5h-1.08q-.194 2.09-1.273 4.117T7.11 12");
}

</style>
