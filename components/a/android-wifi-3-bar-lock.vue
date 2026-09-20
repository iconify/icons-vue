<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3i284bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-wifi-3-bar-lock" /></template>
<style>
.b3i284bem {
  fill: currentColor;
  d: path("M17.37 19q-.37 0-.63-.26t-.26-.628v-2.8q0-.35.26-.6t.63-.25h.11v-1q0-.749.511-1.259t1.259-.51t1.259.51t.51 1.259v1h.112q.35 0 .61.25q.259.25.259.6v2.8q0 .369-.25.629q-.25.259-.62.259zm.88-4.538h2v-1q0-.425-.288-.713t-.712-.288t-.712.288t-.288.713zm-7.316 4.104q-.434-.433-.434-1.066t.434-1.066T12 16t1.066.434q.434.433.434 1.066t-.434 1.066Q12.633 19 12 19t-1.066-.434m-7.747-8.091L1.773 9.062q2.089-1.956 4.721-3.009T12 5t5.506 1.053t4.721 3.009l-.7.719q-.506-.235-1.049-.342t-1.112-.12q-1.627-1.153-3.504-1.736T12 7q-2.466 0-4.74.895t-4.073 2.58M7.2 14.45l-1.408-1.408q1.264-1.22 2.861-1.872q1.597-.65 3.347-.65q.794 0 1.562.145q.767.147 1.507.433q-.369.385-.65.807q-.283.422-.488.916q-.462-.158-.947-.23q-.486-.072-.984-.072q-1.367 0-2.597.5T7.2 14.45");
}

</style>
