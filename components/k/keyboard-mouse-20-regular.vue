<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rcnjv9bsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-mouse-20-regular" /></template>
<style>
.rcnjv9bsl {
  fill: currentColor;
  d: path("M12 5H3.5a.5.5 0 0 0-.5.5v8a.5.5 0 0 0 .5.5h13a.5.5 0 0 0 .5-.5v-2.626c.355-.091.69-.232 1-.411V13.5a1.5 1.5 0 0 1-1.5 1.5h-13A1.5 1.5 0 0 1 2 13.5v-8A1.5 1.5 0 0 1 3.5 4H12zm2.5 7a.5.5 0 0 1 0 1h-9a.5.5 0 0 1 0-1zM6.998 9a.752.752 0 1 1 0 1.505a.752.752 0 0 1 0-1.505m3.004 0a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506m7.393-7C18.28 2 19 2.719 19 3.605V7a3 3 0 1 1-6 0V3.605C13 2.72 13.719 2 14.605 2zm-2.79 1a.606.606 0 0 0-.605.605V7a2 2 0 1 0 4 0V3.605A.606.606 0 0 0 17.395 3H16.5v2.5a.5.5 0 0 1-1 0V3zM5.502 6.5a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506m3 0a.753.753 0 1 1 0 1.506a.753.753 0 0 1 0-1.506m3 1.505L11.42 8h.165z");
}

</style>
