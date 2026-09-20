<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qef-u0b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-delete-outline-sharp" /></template>
<style>
.qef-u0b8c {
  fill: currentColor;
  d: path("M7 6v13zm3.866 14H6V6H5V5h4v-.77h6V5h4v1h-1v4.242q-.213-.048-.494-.068t-.506-.02V6H7v13h3.454q.07.271.187.536q.117.264.224.464m-1.211-3h.5q0-1.056.25-1.78l.25-.724V8h-1zm3.692-5.788q.213-.14.481-.281q.27-.14.52-.227V8h-1zm.222 9.216q-1.414-1.42-1.414-3.432t1.418-3.428q1.42-1.414 3.432-1.414t3.428 1.419q1.414 1.419 1.414 3.431t-1.418 3.428t-3.432 1.414t-3.428-1.418m5.082-1.232l.546-.546l-1.811-1.804v-2.73h-.77v3.046z");
}

</style>
